<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8eeycb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8eeycb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:invision" /></template>
