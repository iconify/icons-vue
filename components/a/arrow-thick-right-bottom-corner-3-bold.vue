<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibwid0w7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibwid0w7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-thick-right-bottom-corner-3-bold" /></template>
