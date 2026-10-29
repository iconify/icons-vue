<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m9su60b7m.css';
import '../../css/t/twz7tgb0j.css';
import '../../css/l/lktwn-bjm.css';
import '../../css/r/r5kh_gsbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m9su60b7m"/><path class="twz7tgb0j wm-a"/><path class="lktwn-bjm"/><path class="r5kh_gsbw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-output-duo" /></template>
