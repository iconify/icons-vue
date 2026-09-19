<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m5zvr65ac.css';
import '../../css/b/beg8en7ps.css';
import '../../css/b/b4cbrjb-x.css';
import '../../css/m/m5y224bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m5zvr65ac"/><path class="beg8en7ps"/><path class="b4cbrjb-x"/><path class="m5y224bqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:derelict-house" /></template>
