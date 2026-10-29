<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1v8--byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1v8--byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:barcode-solid" /></template>
