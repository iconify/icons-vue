<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cplsxkl6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cplsxkl6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-php" /></template>
