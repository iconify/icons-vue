<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4nxybn5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4nxybn5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crankshaft-48-bold" /></template>
