<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flis2iisx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flis2iisx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-fields" /></template>
