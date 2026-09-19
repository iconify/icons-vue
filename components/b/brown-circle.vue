<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0jzh2cjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t0jzh2cjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:brown-circle" /></template>
