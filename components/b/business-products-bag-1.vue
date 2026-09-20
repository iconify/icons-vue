<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssf4moqtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ssf4moqtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-bag-1" /></template>
