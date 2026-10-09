<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp6yplxsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rp6yplxsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cursor-20-bold" /></template>
