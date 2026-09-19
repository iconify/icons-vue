<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tn9td58ck.css';
import '../../css/k/k452hcbmf.css';
import '../../css/c/c2-vn7ifl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tn9td58ck"/><path clip-rule="evenodd" class="k452hcbmf"/><path class="c2-vn7ifl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:dollar-bill-wave" /></template>
