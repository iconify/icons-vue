<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nd93jtbtx.css';
import '../../css/l/ls167c1hb.css';
import '../../css/d/dgi-9-bgx.css';
import '../../css/e/ejovddz-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nd93jtbtx"/><path clip-rule="evenodd" class="ls167c1hb"/><path class="dgi-9-bgx"/><path clip-rule="evenodd" class="ejovddz-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:basket-outline" /></template>
