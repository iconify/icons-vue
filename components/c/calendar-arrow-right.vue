<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phdf0gb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phdf0gb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-arrow-right" /></template>
