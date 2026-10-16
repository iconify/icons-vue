<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcllyhbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dcllyhbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cavity-wall-48-bold" /></template>
