<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w35slqbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w35slqbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-left-48" /></template>
