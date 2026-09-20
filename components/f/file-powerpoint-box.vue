<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1c1x8bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1c1x8bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-powerpoint-box" /></template>
