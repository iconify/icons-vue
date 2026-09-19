<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e5sx4mbfr.css';
import '../../css/w/wl_e0fb9e.css';
import '../../css/e/ewavw_btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e5sx4mbfr"/><path class="wl_e0fb9e"/><path class="ewavw_btk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-add-01" /></template>
