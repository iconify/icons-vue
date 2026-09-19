<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa322bcas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fa322bcas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:euro-outline" /></template>
