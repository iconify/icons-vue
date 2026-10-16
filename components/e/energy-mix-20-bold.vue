<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdest5b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdest5b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-mix-20-bold" /></template>
