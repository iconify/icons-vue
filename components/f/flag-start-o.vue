<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5rhr4i0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m5rhr4i0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flag-start-o" /></template>
