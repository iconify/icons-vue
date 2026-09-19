<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bkna_vbco.css';
import '../../css/e/emiydobjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="bkna_vbco"/><path class="emiydobjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud-thunder" /></template>
