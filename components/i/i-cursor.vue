<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wufx3cn9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="wufx3cn9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:i-cursor" /></template>
