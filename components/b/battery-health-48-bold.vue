<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns5zs0vev.css';
import '../../css/q/qdjmx6jro.css';
import '../../css/y/yaab6pb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ns5zs0vev"/><path class="qdjmx6jro"/><path class="yaab6pb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-health-48-bold" /></template>
