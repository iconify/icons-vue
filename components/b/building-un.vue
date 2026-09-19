<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izjzl7b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="izjzl7b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-un" /></template>
