<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d90rggb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d90rggb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-scan-line" /></template>
