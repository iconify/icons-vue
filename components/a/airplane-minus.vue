<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqp38ebxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqp38ebxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-minus" /></template>
