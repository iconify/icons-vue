<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xqkru5bld.css';
import '../../css/d/dcuv42beu.css';
import '../../css/u/u0i6-8b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xqkru5bld"/><path class="dcuv42beu"/><path class="u0i6-8b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bed-bunk" /></template>
