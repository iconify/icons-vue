<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k1xan88pf.css';
import '../../css/z/z4bbp2bhq.css';
import '../../css/s/sava3rbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k1xan88pf"/><path class="wm-a z4bbp2bhq"/><path class="sava3rbel wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-pen" /></template>
