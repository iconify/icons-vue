<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq16mac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq16mac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-vertical-center-fill" /></template>
