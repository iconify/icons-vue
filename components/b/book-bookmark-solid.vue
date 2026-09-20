<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/staytobvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="staytobvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:book-bookmark-solid" /></template>
