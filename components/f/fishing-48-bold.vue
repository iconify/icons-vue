<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2bu28b8d.css';
import '../../css/u/uhvsvhbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k2bu28b8d"/><path class="uhvsvhbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fishing-48-bold" /></template>
