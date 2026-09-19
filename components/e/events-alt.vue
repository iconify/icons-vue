<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuwtgtn5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zuwtgtn5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:events-alt" /></template>
