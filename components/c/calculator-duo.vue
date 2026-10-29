<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wzr_6bn_j.css';
import '../../css/n/nj6yhupln.css';
import '../../css/l/l7umh3bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wzr_6bn_j"/><path class="nj6yhupln wm-a"/><path class="l7umh3bwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calculator-duo" /></template>
