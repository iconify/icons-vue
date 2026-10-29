<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fuy23-brh.css';
import '../../css/i/irtzjc7wf.css';
import '../../css/v/vbtrpvbhv.css';
import '../../css/u/ukna4qm-o.css';
import '../../css/j/jzul1pbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fuy23-brh wm-k"/><path class="irtzjc7wf wm-a"/><path class="vbtrpvbhv wm-shadow"/><path class="ukna4qm-o wm-k"/><path class="jzul1pbjt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cactus-engrave" /></template>
