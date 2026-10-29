<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n5crp9bgp.css';
import '../../css/l/lgultwbwl.css';
import '../../css/b/b2ekdbbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n5crp9bgp wm-a"/><path class="lgultwbwl wm-k"/><path class="b2ekdbbqw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:face-mask-sketch" /></template>
