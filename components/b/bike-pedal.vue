<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h96bfwb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h96bfwb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bike-pedal" /></template>
