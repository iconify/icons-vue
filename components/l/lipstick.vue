<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y79b0gbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y79b0gbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lipstick" /></template>
