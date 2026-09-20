<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6bpiubko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6bpiubko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-draw-io-filled" /></template>
