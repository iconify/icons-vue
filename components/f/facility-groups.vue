<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd91mzb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fd91mzb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:facility-groups" /></template>
