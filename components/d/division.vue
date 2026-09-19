<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vces4wbou.css';
import '../../css/f/fb_51sb_m.css';
import '../../css/j/jxsnms7hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="vces4wbou"/><circle class="fb_51sb_m"/><path class="jxsnms7hz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:division" /></template>
