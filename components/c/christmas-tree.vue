<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-neo8bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d-neo8bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:christmas-tree" /></template>
