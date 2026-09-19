<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-1rxo8ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-1rxo8ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bezier2" /></template>
