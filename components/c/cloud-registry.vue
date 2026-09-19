<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-y7l7lfv.css';
import '../../css/x/xtad_yvwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-y7l7lfv"/><path class="xtad_yvwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-registry" /></template>
