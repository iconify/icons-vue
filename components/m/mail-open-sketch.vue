<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p5s_0zkai.css';
import '../../css/x/xxc5ztfqi.css';
import '../../css/m/m-qm78bhk.css';
import '../../css/s/sljtjcbnu.css';
import '../../css/b/buul2mbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p5s_0zkai"/><path class="wm-k xxc5ztfqi"/><path class="m-qm78bhk wm-k"/><path class="sljtjcbnu wm-a"/><path class="buul2mbps wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-open-sketch" /></template>
