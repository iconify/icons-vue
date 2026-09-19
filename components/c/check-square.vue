<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m420mflov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="m420mflov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:check-square" /></template>
