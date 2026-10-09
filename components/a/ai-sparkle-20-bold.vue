<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvwn6b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="odvwn6b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ai-sparkle-20-bold" /></template>
