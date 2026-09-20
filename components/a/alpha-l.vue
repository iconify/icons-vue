<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsdj_dbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xsdj_dbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-l" /></template>
