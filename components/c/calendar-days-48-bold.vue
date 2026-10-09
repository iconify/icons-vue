<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwjkdv1oe.css';
import '../../css/h/h0rijs3in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="h0rijs3in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-days-48-bold" /></template>
