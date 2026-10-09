<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdhm6x6mb.css';
import '../../css/h/hlfitnjnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdhm6x6mb"/><path class="hlfitnjnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desert-48-bold" /></template>
