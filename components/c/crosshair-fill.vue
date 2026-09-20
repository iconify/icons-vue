<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oenikccfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oenikccfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crosshair-fill" /></template>
