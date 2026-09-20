<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hucfk3b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hucfk3b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-night-outline" /></template>
