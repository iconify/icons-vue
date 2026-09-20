<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnmapwbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnmapwbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:air-horn" /></template>
