<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6l4_zbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6l4_zbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:crop" /></template>
