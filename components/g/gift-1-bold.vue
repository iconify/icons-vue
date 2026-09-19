<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m05_vsbjb.css';
import '../../css/e/em2pzqy8n.css';
import '../../css/c/cgoh2k0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m05_vsbjb"/><path class="em2pzqy8n"/><path clip-rule="evenodd" class="cgoh2k0px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-1-bold" /></template>
