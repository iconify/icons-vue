<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km_57-b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="km_57-b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:chains" /></template>
