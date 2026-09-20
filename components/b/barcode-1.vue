<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0usfcc2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0usfcc2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:barcode-1" /></template>
