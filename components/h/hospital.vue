<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izi3e6qsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izi3e6qsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hospital" /></template>
