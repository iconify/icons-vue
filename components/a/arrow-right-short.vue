<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkslf5byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkslf5byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-right-short" /></template>
