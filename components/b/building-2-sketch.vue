<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uch8o2bil.css';
import '../../css/k/k8zyftb7o.css';
import '../../css/w/w74syu_wh.css';
import '../../css/j/j5drt-bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uch8o2bil wm-k"/><path class="k8zyftb7o wm-k"/><path class="w74syu_wh wm-a"/><path class="j5drt-bbv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-2-sketch" /></template>
