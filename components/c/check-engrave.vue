<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w2t9kvrcl.css';
import '../../css/e/e5drqabmo.css';
import '../../css/e/eerhch8on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w2t9kvrcl"/><path class="e5drqabmo wm-shadow"/><path class="eerhch8on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-engrave" /></template>
