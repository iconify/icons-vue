<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2568zb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e2568zb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:book-open" /></template>
