<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h47jajpue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h47jajpue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-left" /></template>
