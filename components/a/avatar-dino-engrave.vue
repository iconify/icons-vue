<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hs1vj9b-w.css';
import '../../css/b/b9uz1p94q.css';
import '../../css/s/sd-hmubzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hs1vj9b-w"/><path class="b9uz1p94q wm-shadow"/><path class="sd-hmubzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-dino-engrave" /></template>
