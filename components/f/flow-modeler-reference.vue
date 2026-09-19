<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1za3mggn.css';
import '../../css/s/s130yc3zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l1za3mggn"/><path class="s130yc3zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-modeler-reference" /></template>
