<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quhpu2q1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quhpu2q1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-off" /></template>
