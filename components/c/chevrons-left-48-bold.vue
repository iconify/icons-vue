<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka0ey-ttx.css';
import '../../css/u/uclife8yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ka0ey-ttx"/><path class="uclife8yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-48-bold" /></template>
