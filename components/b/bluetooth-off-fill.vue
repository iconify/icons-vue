<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iumlklekx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iumlklekx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluetooth-off-fill" /></template>
