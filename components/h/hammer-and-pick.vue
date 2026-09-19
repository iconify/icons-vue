<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctx78_e8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ctx78_e8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hammer-and-pick" /></template>
