<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w41mwubps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w41mwubps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-square-filled" /></template>
