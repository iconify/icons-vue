<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og2b0zuoz.css';
import '../../css/f/fi2nkdbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="og2b0zuoz"/><path class="fi2nkdbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copy-48" /></template>
