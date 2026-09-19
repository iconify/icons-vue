<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc1s4iqke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc1s4iqke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:headphones-simple" /></template>
