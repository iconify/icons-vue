<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4-p-yb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4-p-yb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hacker-news-dark" /></template>
