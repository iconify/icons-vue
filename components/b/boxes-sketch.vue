<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j_gfjlg0v.css';
import '../../css/w/w7dtdjb0l.css';
import '../../css/t/t4jvu4b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j_gfjlg0v"/><path class="w7dtdjb0l wm-k"/><path class="t4jvu4b4x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:boxes-sketch" /></template>
