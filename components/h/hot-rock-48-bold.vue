<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igky23bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="igky23bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-rock-48-bold" /></template>
