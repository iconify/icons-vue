<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xco8ivb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xco8ivb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fog-48-bold" /></template>
