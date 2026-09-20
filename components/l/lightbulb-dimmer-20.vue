<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfvs7j2dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfvs7j2dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-dimmer-20" /></template>
