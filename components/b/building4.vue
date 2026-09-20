<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lobq--esr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lobq--esr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:building4" /></template>
