<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tszlukbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tszlukbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-drop-circle-outline" /></template>
