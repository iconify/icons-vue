<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn6lqzhve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn6lqzhve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-strip" /></template>
