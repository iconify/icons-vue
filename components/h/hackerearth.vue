<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czhdg1bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czhdg1bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hackerearth" /></template>
