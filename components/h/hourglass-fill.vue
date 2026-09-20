<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiruu6tbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiruu6tbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hourglass-fill" /></template>
