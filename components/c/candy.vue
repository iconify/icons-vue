<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oimfb3b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oimfb3b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:candy" /></template>
