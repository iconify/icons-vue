<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5li1g69r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5li1g69r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-curve-rise-dash-bold" /></template>
