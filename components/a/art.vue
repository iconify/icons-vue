<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nky12llmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nky12llmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:art" /></template>
