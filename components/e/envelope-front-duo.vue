<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xkzf_trfz.css';
import '../../css/y/yekt9d48r.css';
import '../../css/c/cfmjcfbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xkzf_trfz"/><path class="yekt9d48r"/><path class="cfmjcfbng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-front-duo" /></template>
