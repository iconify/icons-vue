<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykmk5r4vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykmk5r4vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluidcalendar-dark" /></template>
