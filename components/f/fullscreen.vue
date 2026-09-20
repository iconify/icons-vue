<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur5e1fafo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur5e1fafo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fullscreen" /></template>
