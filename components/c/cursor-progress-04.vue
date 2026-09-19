<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upaszux0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upaszux0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-progress-04" /></template>
