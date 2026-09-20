<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rln433b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rln433b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-bold-circle-outline" /></template>
