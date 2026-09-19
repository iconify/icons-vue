<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb3g6wplf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fb3g6wplf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chart-line" /></template>
