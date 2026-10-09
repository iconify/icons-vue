<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/horcrqbac.css';
import '../../css/r/rhi79hntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="horcrqbac"/><path class="rhi79hntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-roll-48-bold" /></template>
