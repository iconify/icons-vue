<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j28mambxy.css';
import '../../css/f/fd5etqajb.css';
import '../../css/l/lg-8n1num.css';
import '../../css/i/itg9jgtim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j28mambxy"/><path class="fd5etqajb wm-shadow"/><path class="lg-8n1num"/><path class="itg9jgtim wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kanban-engrave" /></template>
