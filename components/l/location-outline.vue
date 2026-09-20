<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv-vo6qjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv-vo6qjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:location-outline" /></template>
