<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl-lrubrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-lrubrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-border-right" /></template>
