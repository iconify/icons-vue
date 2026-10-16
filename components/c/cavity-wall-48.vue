<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifyp2_bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ifyp2_bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cavity-wall-48" /></template>
