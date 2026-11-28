<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8d3t5s1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8d3t5s1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:globe-off" /></template>
