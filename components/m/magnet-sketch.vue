<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tojhk50px.css';
import '../../css/g/gdi71gd5j.css';
import '../../css/g/gk_jp9uss.css';
import '../../css/r/r_z17l3ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tojhk50px"/><path class="gdi71gd5j wm-a"/><path class="gk_jp9uss wm-k"/><path class="r_z17l3ee wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:magnet-sketch" /></template>
