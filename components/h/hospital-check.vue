<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyabm2p2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyabm2p2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hospital-check" /></template>
