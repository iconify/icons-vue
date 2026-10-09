<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4-c966ww.css';
import '../../css/a/au8t5v7zm.css';
import '../../css/g/gk48d415h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h4-c966ww"/><path class="au8t5v7zm"/><path class="gk48d415h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:factory-48" /></template>
