<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xqm10ubez.css';
import '../../css/f/fpnj5kbqo.css';
import '../../css/d/dec_aybzw.css';
import '../../css/e/e73kn4beu.css';
import '../../css/e/ezzv083_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xqm10ubez"/><path class="fpnj5kbqo wm-k"/><path class="dec_aybzw wm-k"/><path class="e73kn4beu wm-a"/><path class="ezzv083_y wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-cog-sketch" /></template>
