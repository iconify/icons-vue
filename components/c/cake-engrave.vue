<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f_9g0dbfc.css';
import '../../css/z/zd1talb1t.css';
import '../../css/y/yhtn9ti7t.css';
import '../../css/f/fiogixb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f_9g0dbfc"/><path class="wm-shadow zd1talb1t"/><path class="yhtn9ti7t"/><path class="fiogixb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cake-engrave" /></template>
