<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flxshfbem.css';
import '../../css/n/njuk5dbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="flxshfbem"/><path class="njuk5dbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightbulb-sparkle-48-bold" /></template>
