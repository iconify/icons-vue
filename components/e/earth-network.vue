<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sezzy1b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="sezzy1b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-network" /></template>
