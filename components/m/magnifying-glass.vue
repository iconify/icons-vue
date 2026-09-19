<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc2z0-6oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vc2z0-6oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:magnifying-glass" /></template>
