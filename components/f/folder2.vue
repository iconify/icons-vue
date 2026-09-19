<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjv8-gbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjv8-gbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:folder2" /></template>
