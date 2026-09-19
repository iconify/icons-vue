<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nbq6t4bru.css';
import '../../css/s/sg8-s5bcj.css';
import '../../css/x/x-sjrbcab.css';
import '../../css/w/wg-9_kb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nbq6t4bru"/><path clip-rule="evenodd" class="sg8-s5bcj"/><path class="x-sjrbcab"/><path clip-rule="evenodd" class="wg-9_kb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-tongue-outline" /></template>
