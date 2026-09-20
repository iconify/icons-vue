<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srkmhuxgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="srkmhuxgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:food-toast-bread-toast-breakfast" /></template>
