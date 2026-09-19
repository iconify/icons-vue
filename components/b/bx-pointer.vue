<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt6ij0b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6ij0b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-pointer" /></template>
