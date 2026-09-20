<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-knu7bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-knu7bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-split-vertical" /></template>
