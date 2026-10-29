<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ux2p9gb1d.css';
import '../../css/z/z4bbp2bhq.css';
import '../../css/h/hl1gxsb1a.css';
import '../../css/w/wti3g3byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ux2p9gb1d"/><path class="wm-a z4bbp2bhq"/><path class="hl1gxsb1a wm-s"/><path class="wm-s wti3g3byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-clock" /></template>
