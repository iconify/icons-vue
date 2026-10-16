<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u43i3jb2i.css';
import '../../css/c/c9_dz4bmi.css';
import '../../css/m/m7e0bqrrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u43i3jb2i"/><path class="c9_dz4bmi"/><path class="m7e0bqrrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-leak-48" /></template>
