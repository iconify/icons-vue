<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw4quabhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hw4quabhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-off-48" /></template>
