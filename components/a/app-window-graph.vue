<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wceggdbtg.css';
import '../../css/i/ingyikb1h.css';
import '../../css/u/u0csdv95s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wceggdbtg"/><path class="ingyikb1h"/><path class="u0csdv95s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:app-window-graph" /></template>
