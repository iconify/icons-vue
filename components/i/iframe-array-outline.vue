<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzn2au2sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzn2au2sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iframe-array-outline" /></template>
