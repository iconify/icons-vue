<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/g7w-z6qcd.css';
import '../../css/b/bvan9ac7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="g7w-z6qcd"/><path class="bvan9ac7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:cog" /></template>
