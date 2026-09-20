<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3kxz4x1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3kxz4x1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crop-landscape" /></template>
