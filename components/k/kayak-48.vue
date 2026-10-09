<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj9ruis6z.css';
import '../../css/j/j1qqfackf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fj9ruis6z"/><path class="j1qqfackf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kayak-48" /></template>
