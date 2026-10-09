<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6j5_ubif.css';
import '../../css/d/dpee-7beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6j5_ubif"/><path class="dpee-7beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grass-48-bold" /></template>
