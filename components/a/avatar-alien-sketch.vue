<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jy--pbbbh.css';
import '../../css/x/x5caspqqs.css';
import '../../css/o/o4j8kacgj.css';
import '../../css/z/zvmrzybbz.css';
import '../../css/z/zzq0oubsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jy--pbbbh"/><path class="wm-a x5caspqqs"/><path class="o4j8kacgj wm-k"/><path class="wm-a zvmrzybbz"/><path class="wm-s zzq0oubsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-alien-sketch" /></template>
