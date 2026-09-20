<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5xa376xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5xa376xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:export-fill" /></template>
