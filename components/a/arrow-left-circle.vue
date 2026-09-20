<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndpsoymua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndpsoymua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-circle" /></template>
