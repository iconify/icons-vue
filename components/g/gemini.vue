<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt0us-brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mt0us-brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gemini" /></template>
