<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7iy0jbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7iy0jbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-3-fill" /></template>
