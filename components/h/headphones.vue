<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1q1ws-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1q1ws-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:headphones" /></template>
