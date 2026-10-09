<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbi78gooe.css';
import '../../css/g/guzya4pfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fbi78gooe"/><path class="guzya4pfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fast-48-bold" /></template>
