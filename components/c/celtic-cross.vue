<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phryi43km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phryi43km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:celtic-cross" /></template>
