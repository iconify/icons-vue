<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3d5edgbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3d5edgbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-open-edit-outline" /></template>
