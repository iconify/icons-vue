<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w5j7cdbmb.css';
import '../../css/r/r4pn0xbvk.css';
import '../../css/a/am1vutbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w5j7cdbmb"/><path class="r4pn0xbvk"/><path class="am1vutbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:calendar-week" /></template>
