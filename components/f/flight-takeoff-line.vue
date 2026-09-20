<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqzly4tsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqzly4tsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-takeoff-line" /></template>
