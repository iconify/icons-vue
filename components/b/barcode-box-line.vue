<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3pwhlbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3pwhlbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:barcode-box-line" /></template>
