<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc9bpyb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":897};
const content = `<path class="uc9bpyb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hexagon" /></template>
