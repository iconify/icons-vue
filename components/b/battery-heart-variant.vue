<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhqc-30ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhqc-30ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-heart-variant" /></template>
