<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vescuyerh.css';
import '../../css/d/dyrbljpdb.css';
import '../../css/a/a-a796b8n.css';
import '../../css/g/g2xumw4-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vescuyerh wm-k"/><path class="dyrbljpdb wm-a"/><path class="a-a796b8n wm-k"/><path class="g2xumw4-o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:code-xml-sketch" /></template>
