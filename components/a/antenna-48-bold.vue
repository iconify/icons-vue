<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4w681bdr.css';
import '../../css/j/j-f5_l35o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4w681bdr"/><path class="j-f5_l35o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:antenna-48-bold" /></template>
