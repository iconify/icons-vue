<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scu8uw9wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scu8uw9wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:egg-fried-filled" /></template>
