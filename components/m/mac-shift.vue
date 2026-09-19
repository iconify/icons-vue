<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xle_b1dlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xle_b1dlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mac-shift" /></template>
