<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ir8o7_mqf.css';
import '../../css/y/y99pxgpge.css';
import '../../css/f/f4317cc7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ir8o7_mqf"/><path class="y99pxgpge"/><path class="f4317cc7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gripper" /></template>
