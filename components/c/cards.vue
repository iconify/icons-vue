<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g03_-m85e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g03_-m85e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cards" /></template>
