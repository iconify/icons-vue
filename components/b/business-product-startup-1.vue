<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn8-qiy_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rn8-qiy_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-product-startup-1" /></template>
