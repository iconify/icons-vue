<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2i7u1bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2i7u1bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-fluorescent-tube-outline" /></template>
