<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuzsnn-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wuzsnn-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-search-remove" /></template>
