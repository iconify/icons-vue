<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inn8jvb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inn8jvb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:alert" /></template>
