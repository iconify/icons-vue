<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4detvdxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v4detvdxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-raw" /></template>
