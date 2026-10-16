<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2ike7bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2ike7bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crankshaft-48" /></template>
