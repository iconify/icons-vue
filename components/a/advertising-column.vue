<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inujsab6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inujsab6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:advertising-column" /></template>
