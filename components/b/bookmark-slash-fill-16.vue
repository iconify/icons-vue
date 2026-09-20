<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k14xt0b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k14xt0b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-slash-fill-16" /></template>
