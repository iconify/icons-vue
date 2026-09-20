<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp570eboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp570eboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:karate" /></template>
