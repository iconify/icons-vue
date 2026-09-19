<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ced59lb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ced59lb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:docker-compose" /></template>
