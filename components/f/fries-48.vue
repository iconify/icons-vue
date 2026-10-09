<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1iximrex.css';
import '../../css/f/f7x3lpbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1iximrex"/><path class="f7x3lpbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fries-48" /></template>
