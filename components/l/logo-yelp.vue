<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lje0eit7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lje0eit7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-yelp" /></template>
