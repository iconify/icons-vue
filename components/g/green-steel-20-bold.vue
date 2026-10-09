<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk0e34b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nk0e34b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-steel-20-bold" /></template>
