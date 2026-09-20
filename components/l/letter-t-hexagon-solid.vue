<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4w7b1byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4w7b1byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-hexagon-solid" /></template>
