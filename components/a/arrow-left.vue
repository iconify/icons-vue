<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hue2x_wlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hue2x_wlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left" /></template>
