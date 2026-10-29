<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vtzv2fo-g.css';
import '../../css/s/s2v-wta1e.css';
import '../../css/b/bs6vl3bfj.css';
import '../../css/f/f24vzrb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vtzv2fo-g"/><path class="s2v-wta1e wm-a"/><path class="bs6vl3bfj wm-k"/><path class="f24vzrb4o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baby-sketch" /></template>
