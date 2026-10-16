<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkx3xqbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nkx3xqbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:legend-20" /></template>
