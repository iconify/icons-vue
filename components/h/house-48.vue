<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9czz4bal.css';
import '../../css/e/ef_ersl9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="ef_ersl9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-48" /></template>
