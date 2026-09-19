<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqzd7rbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqzd7rbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-governance-untracked" /></template>
