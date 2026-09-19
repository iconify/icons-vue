<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nk2fk-buj.css';
import '../../css/n/nsrp3pccn.css';
import '../../css/h/h03br7b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nk2fk-buj"/><path class="nsrp3pccn"/><path class="h03br7b3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:door-open-1-duo" /></template>
