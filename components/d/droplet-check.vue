<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4f8m2rpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4f8m2rpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:droplet-check" /></template>
