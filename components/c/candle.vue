<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oa7twqs_h.css';
import '../../css/s/sg0bdz8_g.css';
import '../../css/l/ld_mji7jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oa7twqs_h"/><path class="sg0bdz8_g"/><path class="ld_mji7jh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:candle" /></template>
