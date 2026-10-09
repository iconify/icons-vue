<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzp1g281f.css';
import '../../css/p/plpbozbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzp1g281f"/><path class="plpbozbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-1-48-bold" /></template>
