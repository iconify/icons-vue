<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0dvk7b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0dvk7b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-bold-box" /></template>
