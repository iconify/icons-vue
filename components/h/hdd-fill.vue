<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6d7zo6uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s6d7zo6uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hdd-fill" /></template>
