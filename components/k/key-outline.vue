<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0nzbp1zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0nzbp1zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key-outline" /></template>
