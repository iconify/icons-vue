<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf--d4iuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tf--d4iuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-rotate-right" /></template>
