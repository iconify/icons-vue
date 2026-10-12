<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st531kb5s.css';
import '../../css/e/etimskbbu.css';
import '../../css/r/rw1twdhke.css';
import '../../css/h/hp8bhknya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="st531kb5s"/><path class="etimskbbu"/><path class="rw1twdhke"/><path class="hp8bhknya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-station-48" /></template>
