<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn-_jfbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mn-_jfbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-5-circle-fill" /></template>
