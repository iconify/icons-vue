<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydmm0mbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydmm0mbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:car-auto" /></template>
