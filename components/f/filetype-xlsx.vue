<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duh_o4gwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="duh_o4gwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-xlsx" /></template>
