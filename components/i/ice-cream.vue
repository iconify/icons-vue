<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs-xbhv-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qs-xbhv-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ice-cream" /></template>
