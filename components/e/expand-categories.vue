<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7lp7jw1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7lp7jw1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:expand-categories" /></template>
