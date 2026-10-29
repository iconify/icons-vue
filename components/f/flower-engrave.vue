<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aqikjdb1l.css';
import '../../css/j/jjtf8bcgi.css';
import '../../css/z/zyla41bsz.css';
import '../../css/h/hbi8hhkfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aqikjdb1l wm-k"/><path class="jjtf8bcgi wm-shadow"/><path class="wm-k zyla41bsz"/><path class="hbi8hhkfx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flower-engrave" /></template>
