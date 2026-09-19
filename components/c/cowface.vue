<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfm18fb_m.css';
import '../../css/w/w2mbxhs7a.css';
import '../../css/x/xhtfqplxc.css';
import '../../css/p/p3g_7hp9z.css';
import '../../css/r/rvfbosbgv.css';
import '../../css/s/sbtdt4vjj.css';
import '../../css/i/i1dqrvbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vfm18fb_m"/><path class="w2mbxhs7a"/><path class="xhtfqplxc"/><path class="p3g_7hp9z"/><path class="rvfbosbgv"/><path class="sbtdt4vjj"/><path class="i1dqrvbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cowface" /></template>
