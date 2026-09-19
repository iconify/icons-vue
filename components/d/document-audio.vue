<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxmas2bmc.css';
import '../../css/u/u9olyabjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxmas2bmc"/><path class="u9olyabjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-audio" /></template>
