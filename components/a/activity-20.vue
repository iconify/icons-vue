<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpjz6abop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cpjz6abop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:activity-20" /></template>
