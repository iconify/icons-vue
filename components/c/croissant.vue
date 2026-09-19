<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vyn2gq-gt.css';
import '../../css/k/kt93orw5x.css';
import '../../css/t/tbf9wf6kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vyn2gq-gt"/><path class="kt93orw5x"/><path class="tbf9wf6kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:croissant" /></template>
