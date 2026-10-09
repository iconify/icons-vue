<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpjugbvy.css';
import '../../css/g/gswiw2jgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="gswiw2jgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-bolt-48-bold" /></template>
