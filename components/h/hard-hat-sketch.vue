<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i83db182z.css';
import '../../css/d/dwsa8ob3o.css';
import '../../css/p/p0cq4h5-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i83db182z wm-a"/><path class="dwsa8ob3o wm-k"/><path class="p0cq4h5-v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-hat-sketch" /></template>
