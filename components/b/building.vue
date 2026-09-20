<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpgfkublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wpgfkublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:building" /></template>
