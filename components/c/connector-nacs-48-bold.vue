<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmdr1llum.css';
import '../../css/r/r0z87ttka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mmdr1llum"/><path class="r0z87ttka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-nacs-48-bold" /></template>
