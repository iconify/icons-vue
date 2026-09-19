<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km3o8g18s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="km3o8g18s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:info" /></template>
