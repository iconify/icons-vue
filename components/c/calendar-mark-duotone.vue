<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p_0lkt0mb.css';
import '../../css/m/m6pddwb-m.css';
import '../../css/e/egjof1b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p_0lkt0mb"/><path class="m6pddwb-m"/><path class="egjof1b9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-mark-duotone" /></template>
