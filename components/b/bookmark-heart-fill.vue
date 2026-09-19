<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti-29ubjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ti-29ubjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bookmark-heart-fill" /></template>
