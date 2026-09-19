<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c7iwfpmcu.css';
import '../../css/q/qhe2p8bmz.css';
import '../../css/n/n50ber1gu.css';
import '../../css/w/wzdkftm_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c7iwfpmcu"/><path class="qhe2p8bmz"/><path clip-rule="evenodd" class="n50ber1gu"/><path class="wzdkftm_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:day" /></template>
