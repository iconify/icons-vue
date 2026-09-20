<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cee9hacjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cee9hacjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down-left" /></template>
