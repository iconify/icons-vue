<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd839obzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd839obzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-automation" /></template>
