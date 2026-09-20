<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm59u6zwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm59u6zwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compressed-file-outline" /></template>
