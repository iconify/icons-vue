<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-wrpab9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wrpab9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flame-off" /></template>
