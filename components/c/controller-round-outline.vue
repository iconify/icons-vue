<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1h331y1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1h331y1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-round-outline" /></template>
