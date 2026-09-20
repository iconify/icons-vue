<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqbjj5byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqbjj5byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-music" /></template>
