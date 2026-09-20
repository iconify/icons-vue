<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4i4robuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4i4robuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-drumstick-off-outline" /></template>
