<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvrx_mfoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pvrx_mfoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:filter" /></template>
