<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rul6h_x9m.css';
import '../../css/h/hgjw24b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rul6h_x9m"/><path class="hgjw24b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-label-20-bold" /></template>
