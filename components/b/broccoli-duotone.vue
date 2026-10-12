<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ysj58sbch.css';
import '../../css/t/tvimuc6hh.css';
import '../../css/d/di_j1vbhp.css';
import '../../css/j/jkzy1mcbu.css';
import '../../css/v/vhusiac6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ysj58sbch"/><path class="tvimuc6hh"/><path class="di_j1vbhp"/><path class="jkzy1mcbu"/><path class="vhusiac6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:broccoli-duotone" /></template>
