<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcngc0ydm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcngc0ydm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:earth-fill" /></template>
