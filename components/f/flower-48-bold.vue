<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7kleu9_v.css';
import '../../css/m/mn53fqbfv.css';
import '../../css/u/ulvulp3em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7kleu9_v"/><path class="mn53fqbfv"/><path class="ulvulp3em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flower-48-bold" /></template>
