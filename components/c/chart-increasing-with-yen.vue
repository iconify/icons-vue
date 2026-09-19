<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynna6ub8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ynna6ub8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:chart-increasing-with-yen" /></template>
