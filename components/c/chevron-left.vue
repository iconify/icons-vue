<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx860hber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx860hber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-left" /></template>
