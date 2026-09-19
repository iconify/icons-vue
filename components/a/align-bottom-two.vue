<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5l2_bto.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPUGGMpUY"><path class="nv5l2_bto"/></mask></defs><path mask="url(#SVGPUGGMpUY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-bottom-two" /></template>
