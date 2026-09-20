<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8ogv5b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8ogv5b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-find" /></template>
