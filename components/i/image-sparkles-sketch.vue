<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pj4w296cn.css';
import '../../css/l/l1vadobod.css';
import '../../css/v/vw6k31boc.css';
import '../../css/o/oubua5bfb.css';
import '../../css/r/r4sn81cyt.css';
import '../../css/q/qyjic00ok.css';
import '../../css/j/jftfw_bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pj4w296cn"/><path class="l1vadobod wm-k"/><path class="vw6k31boc wm-a"/><path class="oubua5bfb wm-s"/><path class="r4sn81cyt wm-k"/><path class="qyjic00ok wm-a"/><path class="jftfw_bzx wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-sparkles-sketch" /></template>
