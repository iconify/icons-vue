<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/layxr5bdf.css';
import '../../css/i/i8ycrbbjm.css';
import '../../css/h/hvk1vzbat.css';
import '../../css/c/cw36_6mco.css';
import '../../css/o/orw_fqitx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="layxr5bdf wm-k"/><path class="i8ycrbbjm wm-a"/><path class="hvk1vzbat wm-shadow"/><path class="cw36_6mco wm-a"/><path class="orw_fqitx wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-network-engrave" /></template>
