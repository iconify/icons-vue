<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbb5-g-jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbb5-g-jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-school" /></template>
