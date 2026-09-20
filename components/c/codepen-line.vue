<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fju0sum8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fju0sum8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:codepen-line" /></template>
