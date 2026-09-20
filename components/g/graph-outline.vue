<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdz3jzvqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdz3jzvqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-outline" /></template>
