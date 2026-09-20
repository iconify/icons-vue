<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up7s9rbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up7s9rbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-4-line" /></template>
