<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4cqdubtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e4cqdubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:export" /></template>
