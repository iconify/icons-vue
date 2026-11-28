<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3k-7ccja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3k-7ccja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-clock" /></template>
