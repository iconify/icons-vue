<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc-70lbob.css';
import '../../css/u/ul7pjw58j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc-70lbob"/><path class="ul7pjw58j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-48-bold" /></template>
