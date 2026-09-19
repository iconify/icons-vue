<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc3c8rbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dc3c8rbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bookmarks" /></template>
