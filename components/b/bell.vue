<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrld43bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zrld43bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:bell" /></template>
