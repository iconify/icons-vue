<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcezpobhl.css';
import '../../css/m/m2oqjubvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hcezpobhl"/><path class="m2oqjubvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-negative-20" /></template>
