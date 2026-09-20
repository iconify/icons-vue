<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxtl_ubyj.css';
import '../../css/s/s7-mspfvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxtl_ubyj"/><path class="s7-mspfvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-product-check" /></template>
