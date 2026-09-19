<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es20id4tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es20id4tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cube-alt" /></template>
