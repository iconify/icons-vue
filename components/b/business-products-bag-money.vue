<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmsf81b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qmsf81b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-bag-money" /></template>
