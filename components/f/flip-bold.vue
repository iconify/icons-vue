<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/u4tbqsblh.css';
import '../../css/i/ikozek9sr.css';
import '../../css/e/et_5w2bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="u4tbqsblh"/><path class="ikozek9sr"/><path class="et_5w2bcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flip-bold" /></template>
