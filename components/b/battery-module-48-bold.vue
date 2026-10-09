<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu9rvubvf.css';
import '../../css/w/w-l4ddc4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu9rvubvf"/><path class="w-l4ddc4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-module-48-bold" /></template>
