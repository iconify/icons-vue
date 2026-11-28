<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bvpz28b_m.css';
import '../../css/k/k6y2b5b4m.css';
import '../../css/c/cskso5bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bvpz28b_m"/><path class="k6y2b5b4m"/><path class="cskso5bei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-tree" /></template>
