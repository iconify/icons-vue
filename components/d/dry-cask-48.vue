<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uklt71bum.css';
import '../../css/o/okvl3ohva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uklt71bum"/><path class="okvl3ohva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dry-cask-48" /></template>
