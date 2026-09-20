<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onth24bvb.css';
import '../../css/q/qaw1fhbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="onth24bvb"/><path class="ouiIcon__fillSecondary qaw1fhbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-metrics" /></template>
