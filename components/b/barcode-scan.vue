<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-asay8ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u-asay8ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:barcode-scan" /></template>
