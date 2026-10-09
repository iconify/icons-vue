<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-povvb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-povvb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:i-beam-48" /></template>
