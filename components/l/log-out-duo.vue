<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x6qr2bbqx.css';
import '../../css/y/y-4pm4bgt.css';
import '../../css/r/rn270gbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x6qr2bbqx"/><path class="y-4pm4bgt"/><path class="rn270gbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:log-out-duo" /></template>
