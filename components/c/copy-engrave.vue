<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fu9g10bff.css';
import '../../css/r/rchvh1bpr.css';
import '../../css/z/zvpur5thu.css';
import '../../css/c/c5b0y0tyz.css';
import '../../css/b/b5x9xi0bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fu9g10bff wm-k"/><path class="rchvh1bpr wm-a"/><path class="wm-shadow zvpur5thu"/><path class="c5b0y0tyz wm-k"/><path class="b5x9xi0bu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:copy-engrave" /></template>
