<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo4aw-d5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo4aw-d5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-plus" /></template>
