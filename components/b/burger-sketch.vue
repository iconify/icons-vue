<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/ff4jdybea.css';
import '../../css/g/gtbtb4krd.css';
import '../../css/g/gqeu1eb-b.css';
import '../../css/p/p-js957rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ff4jdybea wm-k"/><path class="gtbtb4krd wm-a"/><path class="gqeu1eb-b wm-k"/><path class="p-js957rr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:burger-sketch" /></template>
