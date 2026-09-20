<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n60pvibmo.css';
import '../../css/k/kouf8lb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n60pvibmo"/><path class="kouf8lb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-product-piggy-bank" /></template>
