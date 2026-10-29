<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dgsjy9b9z.css';
import '../../css/y/yauv4zzce.css';
import '../../css/v/v2r3rlblx.css';
import '../../css/c/c-1i_6wtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dgsjy9b9z"/><path class="wm-a yauv4zzce"/><path class="v2r3rlblx wm-k"/><path class="c-1i_6wtz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-sketch" /></template>
