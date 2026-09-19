<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyjiv_0rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyjiv_0rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-mixed-outline" /></template>
