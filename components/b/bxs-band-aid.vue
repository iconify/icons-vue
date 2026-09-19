<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y95ohhh1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y95ohhh1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-band-aid" /></template>
