<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id3fg2b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="id3fg2b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:droplet-20" /></template>
