<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ec78oob8p.css';
import '../../css/h/hkqlfx1bz.css';
import '../../css/x/xaymihi1d.css';
import '../../css/w/wri5opbdz.css';
import '../../css/u/uanjz8m2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ec78oob8p wm-k"/><path class="hkqlfx1bz wm-a"/><path class="wm-shadow xaymihi1d"/><path class="wm-k wri5opbdz"/><path class="uanjz8m2o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-tree-engrave" /></template>
