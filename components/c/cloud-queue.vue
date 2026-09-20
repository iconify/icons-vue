<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1ao-hb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ao-hb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-queue" /></template>
