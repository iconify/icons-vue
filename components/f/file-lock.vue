<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhmngqbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhmngqbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-lock" /></template>
