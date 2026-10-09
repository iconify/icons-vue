<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6xr_117y.css';
import '../../css/e/ej4s9gber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6xr_117y"/><path class="ej4s9gber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-48-bold" /></template>
