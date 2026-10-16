<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l10uce2pa.css';
import '../../css/o/ou2ox_rmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l10uce2pa"/><path class="ou2ox_rmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dew-48" /></template>
