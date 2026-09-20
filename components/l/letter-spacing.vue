<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsbq87ajf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fsbq87ajf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:letter-spacing" /></template>
