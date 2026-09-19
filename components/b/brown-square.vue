<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdtxzio9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdtxzio9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:brown-square" /></template>
