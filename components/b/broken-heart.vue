<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd1w7wl8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd1w7wl8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:broken-heart" /></template>
