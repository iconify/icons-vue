<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1f9li6sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1f9li6sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:gg" /></template>
