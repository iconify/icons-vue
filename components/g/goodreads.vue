<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-w8v3b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l-w8v3b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:goodreads" /></template>
