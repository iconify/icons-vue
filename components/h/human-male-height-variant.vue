<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajp31hbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajp31hbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-male-height-variant" /></template>
