<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjod6gb0n.css';
import '../../css/r/r1303ebjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjod6gb0n"/><path class="r1303ebjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-budget-48-bold" /></template>
