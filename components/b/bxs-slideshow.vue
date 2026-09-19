<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjtri3beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtri3beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-slideshow" /></template>
