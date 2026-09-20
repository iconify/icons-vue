<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-9-4xo8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-9-4xo8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-dimmer-50" /></template>
