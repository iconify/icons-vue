<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4__ecb7c.css';
import '../../css/h/hc_-pfegj.css';
import '../../css/x/xaulnjbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4__ecb7c"/><path class="hc_-pfegj"/><path class="xaulnjbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-alert-48" /></template>
