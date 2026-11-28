<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frov4f2kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frov4f2kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-refresh" /></template>
