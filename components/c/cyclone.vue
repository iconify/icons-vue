<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh0pj9b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wh0pj9b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cyclone" /></template>
