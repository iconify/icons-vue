<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_dsj84zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_dsj84zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-off-20-bold" /></template>
