<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fq2jchbdb.css';
import '../../css/m/mhf7b27xx.css';
import '../../css/w/w-zm1cbor.css';
import '../../css/l/l78br_b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fq2jchbdb"/><path class="mhf7b27xx"/><path class="w-zm1cbor"/><path class="l78br_b1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-asterisk" /></template>
