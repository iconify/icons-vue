<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jc4l4pbqy.css';
import '../../css/o/ollzt4brz.css';
import '../../css/x/xgz_75bxv.css';
import '../../css/j/ja9zyxbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jc4l4pbqy"/><path class="ollzt4brz wm-a"/><path class="wm-k xgz_75bxv"/><path class="ja9zyxbzw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grape-sketch" /></template>
