<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/ko35661_d.css';
import '../../css/r/ra788cbnf.css';
import '../../css/d/dn4j-pb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ko35661_d"/><path class="ra788cbnf"/><path class="dn4j-pb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:four-point-connection" /></template>
