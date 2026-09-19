<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unhju1fpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unhju1fpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:3d-rotation" /></template>
