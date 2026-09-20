<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxgn1bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvxgn1bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-right-bold-outline" /></template>
