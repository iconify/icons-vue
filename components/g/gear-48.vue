<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvv10bauq.css';
import '../../css/h/h-_usl8fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zvv10bauq"/><path class="h-_usl8fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gear-48" /></template>
