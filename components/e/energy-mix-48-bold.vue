<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2r0g7b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2r0g7b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-mix-48-bold" /></template>
