<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up8refqzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up8refqzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frame-fill" /></template>
