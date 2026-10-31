<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s297ernat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s297ernat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-round" /></template>
