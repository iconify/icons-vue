<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njz8i7bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="njz8i7bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-48-bold" /></template>
