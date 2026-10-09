<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz3rcwbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fz3rcwbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loader-2-20" /></template>
