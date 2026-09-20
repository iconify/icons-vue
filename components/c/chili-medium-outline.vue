<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu90i71ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu90i71ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chili-medium-outline" /></template>
