<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1_h2vbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1_h2vbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:downpointingredtriangle" /></template>
