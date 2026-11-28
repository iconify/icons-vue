<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hhw-sxbck.css';
import '../../css/e/eoonfgcbu.css';
import '../../css/j/jjxa_gbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hhw-sxbck"/><path class="eoonfgcbu"/><path class="jjxa_gbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluetooth-connected-duo" /></template>
