<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izt10ctsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izt10ctsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:isro" /></template>
