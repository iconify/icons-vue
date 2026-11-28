<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m0g21rfgt.css';
import '../../css/l/lbmbikban.css';
import '../../css/f/fwvwu22pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m0g21rfgt"/><path class="lbmbikban"/><path class="fwvwu22pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-from-line-duo" /></template>
