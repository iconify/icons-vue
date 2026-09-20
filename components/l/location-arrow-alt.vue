<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4fdc9b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4fdc9b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:location-arrow-alt" /></template>
