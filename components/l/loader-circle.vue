<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m4xr3bbwi.css';
import '../../css/z/zvhid3bjr.css';
import '../../css/m/mis7vx5md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m4xr3bbwi wm-k"/><path class="wm-k zvhid3bjr"/><path class="mis7vx5md wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:loader-circle" /></template>
