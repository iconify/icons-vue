<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xde85hb4d.css';
import '../../css/f/fsubt_s9k.css';
import '../../css/w/w199b4q7i.css';
import '../../css/m/m2ebxhp-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xde85hb4d"/><path class="fsubt_s9k wm-s"/><path class="w199b4q7i wm-s"/><path class="m2ebxhp-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-cog-duo" /></template>
