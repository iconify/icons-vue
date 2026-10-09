<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5pdqgm9m.css';
import '../../css/c/ctik4kd5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5pdqgm9m"/><path class="ctik4kd5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-bus-48-bold" /></template>
