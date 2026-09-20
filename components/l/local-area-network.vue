<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhpyqpgyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhpyqpgyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-area-network" /></template>
