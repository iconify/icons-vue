<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hamk2lbll.css';
import '../../css/v/vnai25b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hamk2lbll"/><path class="vnai25b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-treasure" /></template>
