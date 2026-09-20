<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swm5vp20p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swm5vp20p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-q-box-outline" /></template>
