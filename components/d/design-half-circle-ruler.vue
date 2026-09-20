<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ho_kb9h.css';
import '../../css/l/l6k3nwb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m5ho_kb9h"/><path class="l6k3nwb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-half-circle-ruler" /></template>
