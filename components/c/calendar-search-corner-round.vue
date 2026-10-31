<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqvvaebnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqvvaebnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-corner-round" /></template>
