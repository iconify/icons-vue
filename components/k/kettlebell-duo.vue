<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzzz-ybzz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nyuapd1pn.css';
import '../../css/s/sc6p5_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzzz-ybzz secondary"/><g class="dt0cm9dhy primary"><path class="nyuapd1pn"/><path class="sc6p5_b7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kettlebell-duo" /></template>
