<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkvraowfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkvraowfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:legend-48-bold" /></template>
