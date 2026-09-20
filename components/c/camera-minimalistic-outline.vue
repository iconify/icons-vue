<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgknkxulm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgknkxulm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-minimalistic-outline" /></template>
