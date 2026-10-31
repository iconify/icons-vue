<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf7wkzb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cf7wkzb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-16-solid" /></template>
