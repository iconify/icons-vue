<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-gxh01qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-gxh01qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-scan-bold" /></template>
