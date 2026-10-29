<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/ssq6xfbfm.css';
import '../../css/s/s9a35_b4n.css';
import '../../css/l/l8un0eb3f.css';
import '../../css/o/o16wlryvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ssq6xfbfm"/><path class="s9a35_b4n wm-a"/><path class="l8un0eb3f wm-k"/><path class="o16wlryvs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crayon-sketch" /></template>
