<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8-to4bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8-to4bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-diamond-outline" /></template>
