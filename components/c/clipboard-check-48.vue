<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-s18fbbr.css';
import '../../css/k/ktyrg6b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-s18fbbr"/><path class="ktyrg6b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-check-48" /></template>
