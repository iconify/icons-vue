<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5k0rbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5k0rbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-skull" /></template>
