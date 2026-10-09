<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubh0c368i.css';
import '../../css/b/b1075nben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ubh0c368i"/><path class="b1075nben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-turbine-48-bold" /></template>
