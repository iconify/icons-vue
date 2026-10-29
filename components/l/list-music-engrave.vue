<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ippf6z_2l.css';
import '../../css/c/cmogpacta.css';
import '../../css/f/fkxjvlbam.css';
import '../../css/e/ezb3ff6ma.css';
import '../../css/a/a3b2f1bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ippf6z_2l wm-k"/><path class="cmogpacta wm-a"/><path class="fkxjvlbam wm-shadow"/><path class="ezb3ff6ma wm-k"/><path class="a3b2f1bep wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-music-engrave" /></template>
