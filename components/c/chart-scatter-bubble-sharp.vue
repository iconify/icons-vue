<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sacp62b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sacp62b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-bubble-sharp" /></template>
