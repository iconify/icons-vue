<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csbhz8b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csbhz8b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:droplet" /></template>
