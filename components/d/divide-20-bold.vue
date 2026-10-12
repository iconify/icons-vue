<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_01joir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nz_01joir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:divide-20-bold" /></template>
