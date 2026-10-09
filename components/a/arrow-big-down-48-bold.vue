<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is8v6-bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="is8v6-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-down-48-bold" /></template>
