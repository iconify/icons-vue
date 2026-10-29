<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jlszr274p.css';
import '../../css/b/b77471bvp.css';
import '../../css/i/ia35t3bos.css';
import '../../css/z/zzfolpdfq.css';
import '../../css/o/o0e_2rhnn.css';
import '../../css/x/xlf7d5bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jlszr274p"/><path class="b77471bvp wm-a"/><path class="ia35t3bos wm-s"/><path class="wm-k zzfolpdfq"/><path class="o0e_2rhnn wm-a"/><path class="wm-s xlf7d5bfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-sun-rain-sketch" /></template>
