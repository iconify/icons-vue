<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msh6ovb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msh6ovb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-child" /></template>
