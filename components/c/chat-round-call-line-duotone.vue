<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/snto2-zvc.css';
import '../../css/q/qnpvard1a.css';
import '../../css/w/wcs8p4ttm.css';
import '../../css/r/r8rap4b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="snto2-zvc"/><path class="qnpvard1a"/><path class="wcs8p4ttm"/><path class="r8rap4b0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-call-line-duotone" /></template>
