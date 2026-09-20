<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw0uamblc.css';
import '../../css/c/c3oi41ban.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/w/wrvqot0ph.css';
import '../../css/z/z8ypd6j8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fw0uamblc"/><path class="c3oi41ban"/><g class="kdz4acc8r"><path class="wrvqot0ph"/><path class="z8ypd6j8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:airplane" /></template>
