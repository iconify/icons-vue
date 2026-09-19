<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1o1fw7_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1o1fw7_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-rotate" /></template>
