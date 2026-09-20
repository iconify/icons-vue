<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq5knvfps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq5knvfps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-box-fill" /></template>
