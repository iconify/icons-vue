<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffjsxmbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ffjsxmbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-star-16" /></template>
