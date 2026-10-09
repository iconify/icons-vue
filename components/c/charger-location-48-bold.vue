<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqi8izblt.css';
import '../../css/e/emg8x4zsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqi8izblt"/><path class="emg8x4zsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-location-48-bold" /></template>
