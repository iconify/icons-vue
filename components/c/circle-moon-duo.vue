<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo01ujvaa.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/u/uv6bwxswk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo01ujvaa secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="uv6bwxswk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-moon-duo" /></template>
