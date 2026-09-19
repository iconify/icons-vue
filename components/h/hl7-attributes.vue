<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwjzqebfb.css';
import '../../css/e/e4snvjyzq.css';
import '../../css/o/oh_sxl0hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kwjzqebfb"/><path class="e4snvjyzq"/><path class="oh_sxl0hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hl7-attributes" /></template>
