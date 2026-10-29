<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/evfmcsq0p.css';
import '../../css/n/n1lt0nmnn.css';
import '../../css/s/s899hubdr.css';
import '../../css/k/kfxyrybec.css';
import '../../css/z/z-bp8mbcj.css';
import '../../css/e/ezif5xbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="evfmcsq0p"/><path class="n1lt0nmnn wm-a"/><path class="s899hubdr wm-s"/><path class="kfxyrybec wm-k"/><path class="wm-a z-bp8mbcj"/><path class="ezif5xbxd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-check-sketch" /></template>
