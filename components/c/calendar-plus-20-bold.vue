<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7qx85bwi.css';
import '../../css/n/nrnabgmon.css';
import '../../css/l/lfyak8xiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="nrnabgmon"/><path class="lfyak8xiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-plus-20-bold" /></template>
