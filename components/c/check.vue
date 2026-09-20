<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfj95vbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfj95vbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check" /></template>
