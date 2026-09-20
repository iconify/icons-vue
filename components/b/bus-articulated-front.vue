<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at882_b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at882_b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-articulated-front" /></template>
