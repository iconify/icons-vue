<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/utgs_bbxu.css';
import '../../css/r/rc9hhabvi.css';
import '../../css/c/cdnnv50mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utgs_bbxu"/><path class="rc9hhabvi"/><path class="cdnnv50mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-trend-down" /></template>
