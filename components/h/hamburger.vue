<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwv4w0b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cwv4w0b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hamburger" /></template>
