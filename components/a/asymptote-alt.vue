<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usi9ys8jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":476,"height":512};
const content = `<path class="usi9ys8jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:asymptote-alt" /></template>
