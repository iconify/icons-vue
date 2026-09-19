<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckq7j1kxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckq7j1kxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chair" /></template>
