<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc9blybmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc9blybmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-play-store" /></template>
