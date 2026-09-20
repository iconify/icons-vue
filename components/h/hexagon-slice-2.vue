<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjh5ppb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjh5ppb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-slice-2" /></template>
