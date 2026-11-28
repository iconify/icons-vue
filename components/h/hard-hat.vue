<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwdamvlhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwdamvlhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hard-hat" /></template>
