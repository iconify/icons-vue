<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8se23fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo8se23fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-c" /></template>
