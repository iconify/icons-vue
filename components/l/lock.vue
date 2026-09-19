<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjt7k-myh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjt7k-myh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:lock" /></template>
