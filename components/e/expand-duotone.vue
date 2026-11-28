<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ardmbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y1ardmbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:expand-duotone" /></template>
