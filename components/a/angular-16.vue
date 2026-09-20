<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhvg8jryb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xhvg8jryb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:angular-16" /></template>
