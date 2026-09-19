<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj7j4ybat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383,"height":512};
const content = `<path class="nj7j4ybat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jenkins" /></template>
