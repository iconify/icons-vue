<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/to-bzow0z.css';
import '../../css/b/bwt7f1bmt.css';
import '../../css/d/dp2cw1ouh.css';
import '../../css/p/pncw32s0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="to-bzow0z"/><path class="bwt7f1bmt wm-k"/><path class="dp2cw1ouh wm-k"/><path class="pncw32s0k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ghost-sketch" /></template>
