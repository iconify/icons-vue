<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ak44dhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ak44dhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lantern-2-fill" /></template>
