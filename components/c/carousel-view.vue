<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re5tqlbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re5tqlbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:carousel-view" /></template>
