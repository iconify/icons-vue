<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zp2593bpl.css';
import '../../css/v/v-n2grb0r.css';
import '../../css/x/xa8yffp9t.css';
import '../../css/j/jchcoxbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zp2593bpl"/><path class="v-n2grb0r wm-a"/><path class="wm-k xa8yffp9t"/><path class="jchcoxbow wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:copy-sketch" /></template>
