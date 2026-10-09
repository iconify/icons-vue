<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzp1g281f.css';
import '../../css/u/u32gxcc6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzp1g281f"/><path class="u32gxcc6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-2-48-bold" /></template>
