<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xddy8fb2y.css';
import '../../css/p/pa-3jhbbm.css';
import '../../css/m/m1th99r3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xddy8fb2y"/><path class="pa-3jhbbm wm-k"/><path class="m1th99r3a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-panda-sketch" /></template>
