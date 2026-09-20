<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnnik6v0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnik6v0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:closed-caption-outline" /></template>
