<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woji7ibvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woji7ibvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-lightbulb-outline" /></template>
