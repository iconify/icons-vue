<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-v3l6b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z-v3l6b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-open-fill-16" /></template>
