<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9vja6rqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e9vja6rqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:arrow-down-bold" /></template>
