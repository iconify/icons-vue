<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrw5zccqv.css';
import '../../css/o/ou7lm9bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vrw5zccqv"/><path class="ou7lm9bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-heart-48-bold" /></template>
