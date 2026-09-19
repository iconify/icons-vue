<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1w90i-5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m1w90i-5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-check-stroke-12" /></template>
