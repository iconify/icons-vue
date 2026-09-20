<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/midlno-ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="midlno-ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gable-roofed-shelter-with-fireplace-and-chimney" /></template>
