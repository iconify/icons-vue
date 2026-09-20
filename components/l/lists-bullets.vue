<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsif9abwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsif9abwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:lists-bullets" /></template>
