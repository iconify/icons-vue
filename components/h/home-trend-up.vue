<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/utgs_bbxu.css';
import '../../css/d/dm68vsz5k.css';
import '../../css/l/l62qqqg8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utgs_bbxu"/><path class="dm68vsz5k"/><path class="l62qqqg8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-trend-up" /></template>
