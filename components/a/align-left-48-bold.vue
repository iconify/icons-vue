<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2irslbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2irslbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-left-48-bold" /></template>
