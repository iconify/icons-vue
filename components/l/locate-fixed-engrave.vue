<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g2wdl1bwg.css';
import '../../css/k/kxrjztx3q.css';
import '../../css/v/v9kvji8te.css';
import '../../css/h/hbi8hhkfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g2wdl1bwg wm-k"/><path class="kxrjztx3q wm-shadow"/><path class="v9kvji8te wm-k"/><path class="hbi8hhkfx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:locate-fixed-engrave" /></template>
