<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtdk27bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtdk27bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:les-libraires" /></template>
