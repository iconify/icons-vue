<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3wg84b-p.css';
import '../../css/i/ikxx9ebbh.css';
import '../../css/z/zm9x9jbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3wg84b-p"/><path class="ikxx9ebbh"/><path class="zm9x9jbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-scooter-48-bold" /></template>
