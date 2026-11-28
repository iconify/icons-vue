<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2rly0bxh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rx0sv3t6f.css';
import '../../css/v/v--amgbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w2rly0bxh"/><g class="dt0cm9dhy primary"><path class="rx0sv3t6f"/><path class="v--amgbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:donut-duo" /></template>
