<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsmyxibdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jsmyxibdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-48" /></template>
