<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjo88abed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo88abed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-off-outline" /></template>
