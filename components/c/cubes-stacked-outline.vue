<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra5zdu2wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra5zdu2wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cubes-stacked-outline" /></template>
