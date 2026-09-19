<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2uek7bnp.css';
import '../../css/e/e4tfsobts.css';
import '../../css/p/pqav0tflk.css';
import '../../css/n/n-d8dzbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGIz9FKedO" x1="45.842" x2="45.842" y1="65.063" y2="2.545" gradientTransform="translate(-2.353 27.316)scale(1.4463)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o2uek7bnp"/><stop offset="1" class="e4tfsobts"/></linearGradient><path class="pqav0tflk"/><path fill="url(#SVGIz9FKedO)" class="n-d8dzbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:grafana-wordmark" /></template>
