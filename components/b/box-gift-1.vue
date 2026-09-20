<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l33qbtbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="l33qbtbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:box-gift-1" /></template>
