<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz-r18bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hz-r18bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:lightbulb-outline" /></template>
