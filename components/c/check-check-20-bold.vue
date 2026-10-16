<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki54017ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ki54017ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-check-20-bold" /></template>
