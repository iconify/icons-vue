<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4ur0fbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ur0fbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:airplane-seat" /></template>
