<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onnxsubqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="onnxsubqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-logo-apple-os-system-apple" /></template>
