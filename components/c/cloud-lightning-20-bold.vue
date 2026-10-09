<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r56gtfh8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r56gtfh8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-lightning-20-bold" /></template>
