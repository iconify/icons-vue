<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5c8t3bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5c8t3bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-help" /></template>
