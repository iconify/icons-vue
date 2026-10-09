<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce6ljt2_d.css';
import '../../css/g/gpwzcjb5p.css';
import '../../css/d/d9livjodx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce6ljt2_d"/><path class="gpwzcjb5p"/><path class="d9livjodx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-ground-48-bold" /></template>
