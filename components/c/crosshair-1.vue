<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5la8q4rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y5la8q4rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:crosshair-1" /></template>
