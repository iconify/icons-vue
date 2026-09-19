<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/obzksubap.css';
import '../../css/n/ndhxy8pex.css';
import '../../css/b/blufi__hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="obzksubap"/><path class="ndhxy8pex"/><path class="blufi__hz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:exclamation-circle" /></template>
