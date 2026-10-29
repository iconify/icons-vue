<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ao6j9663s.css';
import '../../css/y/yldnyfoyo.css';
import '../../css/x/x09uiib3e.css';
import '../../css/g/giai2jb9v.css';
import '../../css/d/dm7wguq1j.css';
import '../../css/m/mye-p1bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ao6j9663s wm-k"/><path class="wm-a yldnyfoyo"/><path class="wm-shadow x09uiib3e"/><path class="giai2jb9v wm-k"/><path class="dm7wguq1j wm-k"/><path class="mye-p1bbs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lollipop-engrave" /></template>
