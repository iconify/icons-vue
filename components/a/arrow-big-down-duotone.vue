<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j798y7bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j798y7bdv primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-down-duotone" /></template>
