<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j60fy-bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j60fy-bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-movies" /></template>
