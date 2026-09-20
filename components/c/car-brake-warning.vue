<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1a-1b7oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1a-1b7oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-warning" /></template>
