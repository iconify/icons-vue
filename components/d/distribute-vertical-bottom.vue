<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trsafe9kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsafe9kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:distribute-vertical-bottom" /></template>
