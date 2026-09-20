<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbkr5uppu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbkr5uppu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-d-circle-outline" /></template>
