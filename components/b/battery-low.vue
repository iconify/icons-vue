<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpc92sept.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpc92sept"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-low" /></template>
