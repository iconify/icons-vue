<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ampl8-clf.css';
import '../../css/d/d81cmo-oy.css';
import '../../css/i/ijl0gbtvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ampl8-clf"/><path class="d81cmo-oy"/><path class="ijl0gbtvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:import-export-48-bold" /></template>
