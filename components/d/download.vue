<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th8d8twet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th8d8twet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:download" /></template>
