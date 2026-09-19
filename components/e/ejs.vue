<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4xqf7hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zo4xqf7hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ejs" /></template>
