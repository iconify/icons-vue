<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fngu76b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fngu76b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left-thin" /></template>
