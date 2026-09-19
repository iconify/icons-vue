<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/likjbtbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="likjbtbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:currency-rupee" /></template>
