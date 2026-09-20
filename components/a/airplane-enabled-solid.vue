<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skwfvjj7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="skwfvjj7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airplane-enabled-solid" /></template>
