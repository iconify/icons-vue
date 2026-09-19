<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6gzcks7d.css';
import '../../css/f/faefp84ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g6gzcks7d"/><path class="faefp84ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-earth" /></template>
