<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3zxnib7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k3zxnib7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-sparkle-stroke-16" /></template>
