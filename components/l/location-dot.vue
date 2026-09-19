<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz6siedjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="sz6siedjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:location-dot" /></template>
