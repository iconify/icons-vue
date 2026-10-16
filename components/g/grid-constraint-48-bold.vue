<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5ew6wg8k.css';
import '../../css/c/clhq3_b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u5ew6wg8k"/><path class="clhq3_b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-constraint-48-bold" /></template>
