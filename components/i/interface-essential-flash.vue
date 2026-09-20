<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uekhz5byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uekhz5byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-flash" /></template>
