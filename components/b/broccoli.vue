<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux334-gix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux334-gix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:broccoli" /></template>
