<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fujozsbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fujozsbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-html5" /></template>
