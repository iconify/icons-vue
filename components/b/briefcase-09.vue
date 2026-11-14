<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-crgbb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-crgbb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-09" /></template>
