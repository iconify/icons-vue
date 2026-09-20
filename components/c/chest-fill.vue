<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1t647en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sk1t647en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chest-fill" /></template>
