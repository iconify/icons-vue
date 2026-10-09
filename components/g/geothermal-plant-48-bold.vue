<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkpyk6brm.css';
import '../../css/f/f61frvbiv.css';
import '../../css/l/lknw7jshi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rkpyk6brm"/><path class="f61frvbiv"/><path class="lknw7jshi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-48-bold" /></template>
