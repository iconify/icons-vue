<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjjddbshj.css';
import '../../css/f/flc82qukb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjjddbshj"/><path class="flc82qukb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crop-48" /></template>
