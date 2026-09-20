<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md2d0gm4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="md2d0gm4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-up-1" /></template>
