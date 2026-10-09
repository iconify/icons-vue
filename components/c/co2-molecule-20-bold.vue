<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-pu_abiq.css';
import '../../css/m/m2fwg6b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-pu_abiq"/><path class="m2fwg6b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-molecule-20-bold" /></template>
