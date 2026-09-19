<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usitz_vjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usitz_vjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clapperboard-play-outline" /></template>
