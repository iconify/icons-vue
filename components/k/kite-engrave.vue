<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nlv1jkb4s.css';
import '../../css/j/jm7s3nbjh.css';
import '../../css/b/bxx_x96bn.css';
import '../../css/z/z209u23kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nlv1jkb4s"/><path class="jm7s3nbjh wm-shadow"/><path class="bxx_x96bn"/><path class="z209u23kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kite-engrave" /></template>
