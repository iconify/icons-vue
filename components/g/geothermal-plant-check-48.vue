<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5a2fp72m.css';
import '../../css/m/mtcc90b-l.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5a2fp72m"/><path class="mtcc90b-l"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-check-48" /></template>
