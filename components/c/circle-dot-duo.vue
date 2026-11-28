<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auorgab-l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/l/lavl0lbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auorgab-l secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="lavl0lbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dot-duo" /></template>
