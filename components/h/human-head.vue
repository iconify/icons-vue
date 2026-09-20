<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibf5nlbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ibf5nlbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:human-head" /></template>
