<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn9jvab9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mn9jvab9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:command-20" /></template>
