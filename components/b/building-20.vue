<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpt327yfs.css';
import '../../css/t/tbow3qh2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gpt327yfs"/><path class="tbow3qh2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-20" /></template>
