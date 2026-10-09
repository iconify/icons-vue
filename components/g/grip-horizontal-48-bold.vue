<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nox51db9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nox51db9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-horizontal-48-bold" /></template>
