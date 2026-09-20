<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqvc2kbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqvc2kbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-high" /></template>
