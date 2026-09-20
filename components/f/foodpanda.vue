<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwn9zcbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwn9zcbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:foodpanda" /></template>
