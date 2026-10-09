<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4cqtybrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y4cqtybrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:direct-current-20-bold" /></template>
