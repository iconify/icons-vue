<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsp1sacfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsp1sacfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:grid" /></template>
