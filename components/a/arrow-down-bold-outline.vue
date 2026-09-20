<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-x-zabat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-x-zabat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-bold-outline" /></template>
