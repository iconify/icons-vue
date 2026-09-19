<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmxlmdkqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmxlmdkqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:car-electric-filled" /></template>
