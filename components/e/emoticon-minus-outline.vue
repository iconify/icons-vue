<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl26lbbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl26lbbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-minus-outline" /></template>
