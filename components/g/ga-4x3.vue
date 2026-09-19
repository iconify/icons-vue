<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cvwcv7zoy.css';
import '../../css/m/m2lu62qxv.css';
import '../../css/p/pld9u5fxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="cvwcv7zoy"/><path class="m2lu62qxv"/><path class="pld9u5fxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ga-4x3" /></template>
