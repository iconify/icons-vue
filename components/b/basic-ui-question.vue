<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g05kqyb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g05kqyb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-question" /></template>
