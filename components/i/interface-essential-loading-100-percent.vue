<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfyy9pk0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bfyy9pk0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-100-percent" /></template>
