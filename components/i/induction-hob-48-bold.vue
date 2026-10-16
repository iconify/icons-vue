<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaet4wb5s.css';
import '../../css/k/kvlw_qbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iaet4wb5s"/><path class="kvlw_qbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:induction-hob-48-bold" /></template>
