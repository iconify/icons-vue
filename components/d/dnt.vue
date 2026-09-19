<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us9wupb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="us9wupb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dnt" /></template>
