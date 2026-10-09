<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-zbgc76c.css';
import '../../css/n/ny48sabtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-zbgc76c"/><path class="ny48sabtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dashboard-48" /></template>
