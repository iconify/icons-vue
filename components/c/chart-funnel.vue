<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/ppt3q08ns.css';
import '../../css/a/az6mvhbpu.css';
import '../../css/f/f221bg_-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ppt3q08ns"/><path class="az6mvhbpu"/><path class="f221bg_-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-funnel" /></template>
