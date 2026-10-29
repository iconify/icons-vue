<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o_kozsbwc.css';
import '../../css/o/olg4m4bgm.css';
import '../../css/n/n9fzp5b5o.css';
import '../../css/r/rp9c5jbdr.css';
import '../../css/x/xq8rrbbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o_kozsbwc wm-a"/><path class="olg4m4bgm wm-s"/><path class="n9fzp5b5o wm-k"/><path class="rp9c5jbdr wm-a"/><path class="wm-s xq8rrbbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:love-scroll-sketch" /></template>
