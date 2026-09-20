<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fha4lnzyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fha4lnzyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bunk-bed" /></template>
