<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6w-o8_8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h6w-o8_8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fire-flame-simple" /></template>
