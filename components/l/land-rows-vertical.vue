<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tct91jbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tct91jbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-rows-vertical" /></template>
