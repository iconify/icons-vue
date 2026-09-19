<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdvs7m46w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mdvs7m46w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:aperture" /></template>
