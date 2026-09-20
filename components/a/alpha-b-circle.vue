<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfnh49bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfnh49bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-b-circle" /></template>
