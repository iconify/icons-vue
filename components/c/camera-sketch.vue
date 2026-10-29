<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gh8cru6va.css';
import '../../css/p/phhcb1buc.css';
import '../../css/x/xmz6v6vvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gh8cru6va"/><path class="phhcb1buc wm-k"/><path class="wm-a xmz6v6vvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:camera-sketch" /></template>
