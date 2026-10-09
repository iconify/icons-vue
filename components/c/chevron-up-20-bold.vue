<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2kyd2joj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p2kyd2joj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-up-20-bold" /></template>
