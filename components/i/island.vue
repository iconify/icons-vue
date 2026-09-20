<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9j_5s-yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9j_5s-yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:island" /></template>
