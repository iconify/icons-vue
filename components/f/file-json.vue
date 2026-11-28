<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ema-29wwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ema-29wwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-json" /></template>
