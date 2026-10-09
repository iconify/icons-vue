<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqszs5bfa.css';
import '../../css/e/et3b916ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cqszs5bfa"/><path class="et3b916ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-arc-furnace-48-bold" /></template>
