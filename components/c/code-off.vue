<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t7xt40b-m.css';
import '../../css/m/ms8y08bns.css';
import '../../css/x/xxt8oxbcp.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="t7xt40b-m"/><path clip-rule="evenodd" class="ms8y08bns"/><path clip-rule="evenodd" class="xxt8oxbcp"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:code-off" /></template>
