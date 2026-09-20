<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra4dz9bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4dz9bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f5" /></template>
