<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d82zkm3mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d82zkm3mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-list" /></template>
