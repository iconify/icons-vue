<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyhjwxb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uyhjwxb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:favicon" /></template>
