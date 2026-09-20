<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ve0iaje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y_ve0iaje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-merge-queue-16" /></template>
