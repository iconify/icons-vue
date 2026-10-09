<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxju_n3um.css';
import '../../css/f/fow8b5buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nxju_n3um"/><path class="fow8b5buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatwave-48" /></template>
