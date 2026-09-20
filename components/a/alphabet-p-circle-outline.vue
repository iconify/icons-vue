<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1hq75p3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1hq75p3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-p-circle-outline" /></template>
