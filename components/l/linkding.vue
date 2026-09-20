<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy8m0sbcq.css';
import '../../css/e/etynb-byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="zy8m0sbcq"/><path class="etynb-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkding" /></template>
