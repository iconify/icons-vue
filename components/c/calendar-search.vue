<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv2z-r7bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2z-r7bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-search" /></template>
