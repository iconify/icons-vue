<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cioctv_tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cioctv_tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:houzz-box" /></template>
