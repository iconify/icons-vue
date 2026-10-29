<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ca6loi6wc.css';
import '../../css/s/spndp72wt.css';
import '../../css/w/w38nzkbws.css';
import '../../css/q/q5yic0brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ca6loi6wc"/><path class="spndp72wt wm-k"/><path class="w38nzkbws wm-k"/><path class="q5yic0brb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-open-sketch" /></template>
