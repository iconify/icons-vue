<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9owf8b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":416};
const content = `<path class="l9owf8b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:invert-colors" /></template>
