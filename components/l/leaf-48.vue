<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pixuu6bja.css';
import '../../css/q/qlh3x2h3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pixuu6bja"/><path class="qlh3x2h3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leaf-48" /></template>
