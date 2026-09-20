<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo_0ynbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo_0ynbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-quote-open" /></template>
