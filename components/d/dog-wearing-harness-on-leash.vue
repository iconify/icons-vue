<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8x1_xoez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l8x1_xoez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-wearing-harness-on-leash" /></template>
