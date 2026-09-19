<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ld2sbji.css';
import '../../css/b/bswnp6bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_ld2sbji"/><path class="bswnp6bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-unstructured-data-processor" /></template>
