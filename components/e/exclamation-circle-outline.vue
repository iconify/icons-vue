<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sui3szzzd.css';
import '../../css/w/whtc4r5ex.css';
import '../../css/v/vq4wuwbzl.css';
import '../../css/s/suljz2g3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sui3szzzd"/><path clip-rule="evenodd" class="whtc4r5ex"/><path class="vq4wuwbzl"/><path clip-rule="evenodd" class="suljz2g3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation-circle-outline" /></template>
