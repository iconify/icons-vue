<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnam857uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnam857uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-electric-outline" /></template>
