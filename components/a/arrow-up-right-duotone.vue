<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy1u76bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy1u76bbj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-right-duotone" /></template>
