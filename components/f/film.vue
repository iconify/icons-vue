<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmg3ecoif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1664};
const content = `<path class="wmg3ecoif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:film" /></template>
