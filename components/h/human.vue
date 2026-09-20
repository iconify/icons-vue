<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5l0-3b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c5l0-3b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:human" /></template>
