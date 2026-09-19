<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cavawnw9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="cavawnw9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hourglass-end" /></template>
