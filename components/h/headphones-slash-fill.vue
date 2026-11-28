<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cttyy7b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cttyy7b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:headphones-slash-fill" /></template>
