<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m78btob1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m78btob1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-in-gable-roofed-shelter" /></template>
