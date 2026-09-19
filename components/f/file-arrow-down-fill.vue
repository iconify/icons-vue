<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq7e5gbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vq7e5gbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-arrow-down-fill" /></template>
