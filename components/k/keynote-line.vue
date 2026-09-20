<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc7puxpvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc7puxpvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:keynote-line" /></template>
