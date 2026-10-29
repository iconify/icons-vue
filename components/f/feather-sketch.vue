<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l8a49gbqf.css';
import '../../css/s/sd46-ebbq.css';
import '../../css/n/nghqmlwjd.css';
import '../../css/o/ozvja8n8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l8a49gbqf wm-k"/><path class="sd46-ebbq wm-a"/><path class="nghqmlwjd wm-k"/><path class="ozvja8n8e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:feather-sketch" /></template>
