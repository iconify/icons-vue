<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4w9tabhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4w9tabhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-vertical-48-bold" /></template>
