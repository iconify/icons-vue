<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbxy78esr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbxy78esr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-unordered-16" /></template>
