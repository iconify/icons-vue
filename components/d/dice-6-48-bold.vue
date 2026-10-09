<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzp1g281f.css';
import '../../css/r/rrgrb3b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzp1g281f"/><path class="rrgrb3b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-6-48-bold" /></template>
