<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8wlneb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j8wlneb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:magnifying-glass-x-fill" /></template>
