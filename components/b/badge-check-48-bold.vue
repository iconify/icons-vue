<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si1030bhs.css';
import '../../css/l/lp5-n4bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si1030bhs"/><path class="lp5-n4bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-check-48-bold" /></template>
