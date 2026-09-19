<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaegksbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="uaegksbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:heart-o" /></template>
