<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6go87dht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e6go87dht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-desert-cotton-candy" /></template>
