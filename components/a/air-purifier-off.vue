<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u459c10xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u459c10xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:air-purifier-off" /></template>
