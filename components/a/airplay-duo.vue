<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jrn23ccbu.css';
import '../../css/o/ozbrujcbd.css';
import '../../css/r/rsai_abhp.css';
import '../../css/w/w62x13bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jrn23ccbu"/><path class="ozbrujcbd wm-a"/><path class="rsai_abhp wm-a"/><path class="w62x13bmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:airplay-duo" /></template>
