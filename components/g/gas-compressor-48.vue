<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbe2gqb6b.css';
import '../../css/f/fn_f7s4pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbe2gqb6b"/><path class="fn_f7s4pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-compressor-48" /></template>
