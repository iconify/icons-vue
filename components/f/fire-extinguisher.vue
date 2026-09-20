<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g35904bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g35904bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:fire-extinguisher" /></template>
