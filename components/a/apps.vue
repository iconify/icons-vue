<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa6ra5b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fa6ra5b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:apps" /></template>
