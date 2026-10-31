<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-zx8m0by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-zx8m0by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barcode-duotone-round" /></template>
