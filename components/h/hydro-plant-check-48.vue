<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4__ecb7c.css';
import '../../css/h/hc_-pfegj.css';
import '../../css/x/xvk022b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4__ecb7c"/><path class="hc_-pfegj"/><path class="xvk022b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-check-48" /></template>
