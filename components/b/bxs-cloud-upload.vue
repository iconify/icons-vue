<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh49xw4sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh49xw4sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cloud-upload" /></template>
