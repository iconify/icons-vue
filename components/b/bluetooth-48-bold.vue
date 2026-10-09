<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp09m-bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gp09m-bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bluetooth-48-bold" /></template>
