<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmsvdkbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gmsvdkbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation-circle-fill" /></template>
