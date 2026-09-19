<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syq1gcbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="syq1gcbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-heart" /></template>
