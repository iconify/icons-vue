<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v72t6dbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v72t6dbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:alphabet-uppercase" /></template>
