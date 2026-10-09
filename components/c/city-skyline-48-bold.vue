<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw5ycab-f.css';
import '../../css/o/otkch_brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uw5ycab-f"/><path class="otkch_brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:city-skyline-48-bold" /></template>
