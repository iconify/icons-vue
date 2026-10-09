<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk51r8bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fk51r8bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-snow-20-bold" /></template>
