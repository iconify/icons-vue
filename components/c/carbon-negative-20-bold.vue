<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4n2q8cza.css';
import '../../css/k/kehgtcamx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h4n2q8cza"/><path class="kehgtcamx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-negative-20-bold" /></template>
