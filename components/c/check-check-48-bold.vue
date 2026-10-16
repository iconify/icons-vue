<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khuzr9qny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khuzr9qny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-check-48-bold" /></template>
