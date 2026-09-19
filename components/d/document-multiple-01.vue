<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdp22ib8n.css';
import '../../css/s/sz152uiha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdp22ib8n"/><path class="sz152uiha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-multiple-01" /></template>
