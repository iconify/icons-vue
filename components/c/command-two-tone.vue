<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fecg7fbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fecg7fbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:command-two-tone" /></template>
