<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb6s7laxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tb6s7laxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-status" /></template>
