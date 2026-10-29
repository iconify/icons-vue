<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fyc56sbip.css';
import '../../css/s/ser6vbbjj.css';
import '../../css/b/bf3cxvlkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fyc56sbip"/><path class="ser6vbbjj wm-shadow"/><path class="bf3cxvlkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-commit-engrave" /></template>
