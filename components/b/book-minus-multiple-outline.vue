<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n09x0rbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n09x0rbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-minus-multiple-outline" /></template>
