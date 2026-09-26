<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf669qbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf669qbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-bold" /></template>
