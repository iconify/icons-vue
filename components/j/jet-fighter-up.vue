<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4k29qbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4k29qbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:jet-fighter-up" /></template>
