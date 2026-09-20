<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9_q2hzyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9_q2hzyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-search-outline" /></template>
