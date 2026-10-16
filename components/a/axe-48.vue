<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwf5pgm1r.css';
import '../../css/d/d_be55btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uwf5pgm1r"/><path class="d_be55btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:axe-48" /></template>
