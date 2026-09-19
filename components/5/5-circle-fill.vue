<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okaphv3fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okaphv3fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:5-circle-fill" /></template>
