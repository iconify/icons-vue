<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgnf151la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgnf151la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-vertical" /></template>
