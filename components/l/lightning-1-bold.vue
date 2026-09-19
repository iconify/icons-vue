<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt2r9xb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2r9xb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lightning-1-bold" /></template>
