<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/ffhs8jb2d.css';
import '../../css/o/oeli91cgn.css';
import '../../css/e/ev7y4dbmx.css';
import '../../css/l/lztux4j4y.css';
import '../../css/j/jj7r4xgjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ffhs8jb2d wm-k"/><path class="oeli91cgn wm-a"/><path class="ev7y4dbmx wm-shadow"/><path class="lztux4j4y wm-k"/><path class="jj7r4xgjd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-engrave" /></template>
