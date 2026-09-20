<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwm3unbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwm3unbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:circle-question-solid" /></template>
