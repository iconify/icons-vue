<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waoq3bcbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waoq3bcbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:apple-full-outline" /></template>
