<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xdroklb6f.css';
import '../../css/x/xjhgi0g1x.css';
import '../../css/p/pf9mtmbdy.css';
import '../../css/z/zbv0h6bgp.css';
import '../../css/e/e_hvle-fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xdroklb6f"/><path class="wm-a xjhgi0g1x"/><path class="pf9mtmbdy wm-shadow"/><path class="wm-k zbv0h6bgp"/><path class="e_hvle-fh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folders-engrave" /></template>
