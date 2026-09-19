<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w678jfb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w678jfb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:benchmark" /></template>
