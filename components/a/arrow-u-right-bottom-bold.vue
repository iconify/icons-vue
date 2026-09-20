<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ra-1bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ra-1bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-right-bottom-bold" /></template>
