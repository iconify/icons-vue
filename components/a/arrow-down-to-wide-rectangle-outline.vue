<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7qs3tb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c7qs3tb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-to-wide-rectangle-outline" /></template>
