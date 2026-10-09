<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rarcuc5bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rarcuc5bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-20-bold" /></template>
