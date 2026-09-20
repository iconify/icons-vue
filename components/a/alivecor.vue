<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgqxapb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":350,"height":44};
const content = `<path class="zgqxapb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alivecor" /></template>
