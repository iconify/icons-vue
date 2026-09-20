<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj9s6j9ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aj9s6j9ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-repo-16" /></template>
