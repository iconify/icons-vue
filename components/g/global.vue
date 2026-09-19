<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzi-y4bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tzi-y4bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:global" /></template>
