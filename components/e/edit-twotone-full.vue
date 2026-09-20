<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gutru8b1o.css';
import '../../css/c/c8_y0rbst.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b8o7ubb2r.css';
import '../../css/q/q_1ubx7zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gutru8b1o"><path fill-opacity="0" stroke-dashoffset="44" class="c8_y0rbst"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.3s" dur="0.5s" to="0"/><animate fill="freeze" attributeName="fill-opacity" begin="1s" dur="0.15s" to=".3"/></path><g class="ft5dv1b6b"><path class="b8o7ubb2r"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.3s" values="20;0"/></path><path stroke-dashoffset="8" class="q_1ubx7zw"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.8s" dur="0.2s" to="0"/></path></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:edit-twotone-full" /></template>
