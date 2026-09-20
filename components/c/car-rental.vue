<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaqegsb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jaqegsb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:car-rental" /></template>
