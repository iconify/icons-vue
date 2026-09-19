<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bto7pc17j.css';
import '../../css/k/kp2-bibah.css';
import '../../css/q/qfoyfkmvy.css';
import '../../css/p/pqh64-bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bto7pc17j"/><path class="kp2-bibah"/><path class="qfoyfkmvy"/><path class="pqh64-bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:binoculars-1-outline" /></template>
