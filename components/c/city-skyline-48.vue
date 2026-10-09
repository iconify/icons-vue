<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyn0tjbsp.css';
import '../../css/f/f9-7d2bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyn0tjbsp"/><path class="f9-7d2bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:city-skyline-48" /></template>
