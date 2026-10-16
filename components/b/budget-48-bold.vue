<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pz3rxhk.css';
import '../../css/q/qu3n5acxu.css';
import '../../css/o/osw6h0b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="qu3n5acxu"/><path class="osw6h0b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:budget-48-bold" /></template>
