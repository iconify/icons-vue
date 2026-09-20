<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rss44_aio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rss44_aio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar3-filled" /></template>
