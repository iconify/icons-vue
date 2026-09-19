<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u20pfbbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u20pfbbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:glasspanel-door-closed" /></template>
