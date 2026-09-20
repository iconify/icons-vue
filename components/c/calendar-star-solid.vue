<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whge_h7ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="whge_h7ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calendar-star-solid" /></template>
