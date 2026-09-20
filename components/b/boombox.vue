<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz47rj2ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz47rj2ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boombox" /></template>
