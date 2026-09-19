<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuxbbqk4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vuxbbqk4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-justify-fill-16" /></template>
