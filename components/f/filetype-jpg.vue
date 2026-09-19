<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0c9-dp9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b0c9-dp9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-jpg" /></template>
