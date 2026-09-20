<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84quwacf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w84quwacf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-y" /></template>
