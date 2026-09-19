<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tbfy26nss.css';
import '../../css/t/trec43gzc.css';
import '../../css/x/xc-4gu4gl.css';
import '../../css/f/fy51l8b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tbfy26nss"/><path clip-rule="evenodd" class="trec43gzc"/><path clip-rule="evenodd" class="xc-4gu4gl"/><path class="fy51l8b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:envelope-open-note" /></template>
