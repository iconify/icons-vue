<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_r0tjbwq.css';
import '../../css/d/duhh5kbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r0tjbwq"/><path clip-rule="evenodd" class="duhh5kbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bar-chart-dollar" /></template>
