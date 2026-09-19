<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6uie1dvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6uie1dvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-mixed-dollar-outline" /></template>
