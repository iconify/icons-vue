<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv920pb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hv920pb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:bitcoin" /></template>
