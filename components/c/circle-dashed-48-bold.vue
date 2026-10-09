<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iom95xbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iom95xbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circle-dashed-48-bold" /></template>
