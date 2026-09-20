<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjxocub0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":28};
const content = `<path class="gjxocub0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:attio" /></template>
