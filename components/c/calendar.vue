<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/s/sj5m28f3q.css';
import '../../css/y/y-qaprb-g.css';
import '../../css/m/mue6u3r5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="sj5m28f3q"/><path class="y-qaprb-g"/><path class="mue6u3r5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:calendar" /></template>
