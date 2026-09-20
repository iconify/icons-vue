<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if7dj2d5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if7dj2d5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bluetooth-off" /></template>
