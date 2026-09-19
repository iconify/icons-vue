<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w603acbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w603acbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-hydro" /></template>
