<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/coatur0dk.css';
import '../../css/a/amwvzj90s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="coatur0dk"/><path class="amwvzj90s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:floppy-disk-outline" /></template>
