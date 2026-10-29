<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/id3l-eb5x.css';
import '../../css/r/rb1hythup.css';
import '../../css/s/sumqrmj4j.css';
import '../../css/b/bsj_9-otn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="id3l-eb5x"/><path class="rb1hythup wm-a"/><path class="sumqrmj4j wm-k"/><path class="bsj_9-otn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-drive-sketch" /></template>
