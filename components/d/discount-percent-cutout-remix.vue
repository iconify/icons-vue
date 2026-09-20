<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sza43pt6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sza43pt6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:discount-percent-cutout-remix" /></template>
