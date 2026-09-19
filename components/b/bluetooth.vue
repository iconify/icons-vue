<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb3eeh2at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":432};
const content = `<path class="eb3eeh2at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bluetooth" /></template>
