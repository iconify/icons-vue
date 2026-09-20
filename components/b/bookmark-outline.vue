<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn-5o7bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jn-5o7bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bookmark-outline" /></template>
