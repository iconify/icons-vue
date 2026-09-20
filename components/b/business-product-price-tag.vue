<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bplaobd3f.css';
import '../../css/x/x7qp0hbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bplaobd3f"/><path class="x7qp0hbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-product-price-tag" /></template>
