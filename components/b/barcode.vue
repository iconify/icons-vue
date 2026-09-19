<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qykrqjwin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="qykrqjwin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:barcode" /></template>
