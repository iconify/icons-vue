<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iq9dzactc.css';
import '../../css/o/ohj00hbiv.css';
import '../../css/n/nrwtu07fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="iq9dzactc"/><path class="ohj00hbiv"/><path class="nrwtu07fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:image-duo" /></template>
