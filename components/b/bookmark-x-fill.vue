<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epy770bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="epy770bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bookmark-x-fill" /></template>
